gating-layer-size: [32, 32]
max-path-num: 20
replay-ratio: 1
train-step-num: 1
gamma: 0.955
task-weight: 0.5
expert-num: 4
loss-output-smooth-coeff: 2.0
loss-entropy-coeff: 0.0
critic-lr: 0.0003
actor-lr: 0.0003
dsr-gait-period: 0.6
critic-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
actor-l2-reg: 0.0003
actor-weight-decay: 1e-06
loss-output-diff-coeff: 0
expert-index: None
squash-action: True
Physics-frequency: 1000
joint-interpolation: True
prioritized-exp-replay: True
filter-torque: False
epoch-num: 500
bullet-default-PD: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-train-time: 10
critic-weight-decay: 1e-06
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-index: None
gating-activation-fn: ['relu', 'relu', 'None']
rollout-step-num: 1
record-start-size: 10000.0
replay-start-size: 10000
state-dim: 25
LLC-frequency: 500
filter-action: True
dsr-gait-freq: 1.667
max-test-time: 10
critic-l2-reg: 0.0003
imitation-weight: 0.5
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
render-eval: False
max-path-step: 5000
interpolation: False
epoch-step-num: 5000000
loss-output-bound-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
total-step-num: 2500000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
tau: 0.001
actor-layer-size: [256, 256]
action-dim: 12
max-step-num: 2500000000
n-step: 1
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
reward-scale: 0.1
replay-buffer-size: 1000000
test-num: 4
max-episode-num: 5000000
HLC-frequency: 25
