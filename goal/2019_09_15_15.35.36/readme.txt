gating-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
max-train-time: 10
n-step: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-entropy-coeff: 0.0
critic-l2-reg: 0.0003
task-weight: 0.5
train-step-num: 1
total-step-num: 2500000000
imitation-weight: 0.5
epoch-num: 500
max-step-num: 2500000000
expert-index: None
gating-index: None
tau: 0.001
test-num: 4
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
Physics-frequency: 1000
action-dim: 12
prioritized-exp-replay: True
env-id: HumanoidBalanceFilter-v0
HLC-frequency: 25
critic-layer-size: [256, 256]
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
loss-output-smooth-coeff: 2.0
replay-start-size: 10000
replay-ratio: 1
max-path-num: 20
actor-l2-reg: 0.0003
actor-layer-size: [256, 256]
replay-buffer-size: 1000000
bullet-default-PD: False
batch-size: 128
expert-num: 4
actor-activation-fn: ['relu', 'relu', 'None']
dsr-gait-freq: 1.667
loss-output-bound-coeff: 0.0
render-eval: False
squash-action: True
dsr-gait-period: 0.6
max-episode-num: 5000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
rollout-step-num: 1
actor-lr: 0.0003
state-dim: 25
actor-weight-decay: 1e-06
epoch-step-num: 5000000
max-test-time: 10
LLC-frequency: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gamma: 0.955
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-action: True
record-start-size: 10000.0
gating-layer-size: [32, 32]
interpolation: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
critic-weight-decay: 1e-06
max-path-step: 5000
