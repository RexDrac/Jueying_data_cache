total-step-num: 2500000000
LLC-frequency: 500
train-step-num: 1
dsr-gait-freq: 1.667
test-num: 4
Physics-frequency: 1000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 25
env-id: HumanoidBalanceFilter-v0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
imitation-weight: 0.5
expert-num: 4
replay-ratio: 1
action-dim: 12
tau: 0.001
critic-l2-reg: 0.0003
filter-action: True
dsr-gait-period: 0.6
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-lr: 0.0003
max-episode-num: 5000000
replay-start-size: 10000
actor-weight-decay: 1e-06
reward-scale: 0.1
task-weight: 0.5
max-step-num: 2500000000
HLC-frequency: 25
critic-weight-decay: 1e-06
loss-output-diff-coeff: 0
gating-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
max-test-time: 10
rollout-step-num: 1
replay-buffer-size: 1000000
batch-size: 128
loss-entropy-coeff: 0.0
gamma: 0.955
max-train-time: 10
actor-layer-size: [256, 256]
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
gating-layer-size: [32, 32]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
bullet-default-PD: False
joint-interpolation: True
max-path-step: 5000
epoch-num: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
n-step: 1
record-start-size: 10000.0
actor-l2-reg: 0.0003
epoch-step-num: 5000000
squash-action: True
filter-torque: False
expert-index: None
max-path-num: 20
render-eval: False
prioritized-exp-replay: True
interpolation: False
gating-index: None
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-smooth-coeff: 1.0
